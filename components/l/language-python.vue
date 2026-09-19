<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoyz_kbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="yoyz_kbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:language-python" /></template>
