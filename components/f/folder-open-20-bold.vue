<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp3cjxxjv.css';
import '../../css/x/xranyficx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tp3cjxxjv"/><path class="xranyficx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-open-20-bold" /></template>
