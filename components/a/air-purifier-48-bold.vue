<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svb9bze3d.css';
import '../../css/p/ps1xh1lfy.css';
import '../../css/c/czclwmg1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="svb9bze3d"/><path class="ps1xh1lfy"/><path class="czclwmg1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-purifier-48-bold" /></template>
