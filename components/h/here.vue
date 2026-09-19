<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b54907i9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b54907i9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:here" /></template>
