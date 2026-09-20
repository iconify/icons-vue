<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlif8lbav.css';
import '../../css/f/f72_8xqoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlif8lbav"/><path class="f72_8xqoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:blank-duotone" /></template>
