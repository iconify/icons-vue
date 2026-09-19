<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary-g3wyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ary-g3wyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:magnet" /></template>
