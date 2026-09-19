<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q02x0dbpu.css';
import '../../css/j/jupl2yb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q02x0dbpu"/><path class="jupl2yb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:coreui" /></template>
