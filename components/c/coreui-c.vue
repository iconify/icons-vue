<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4mh9zb-o.css';
import '../../css/b/bpl1kribr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4mh9zb-o"/><path class="bpl1kribr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:coreui-c" /></template>
