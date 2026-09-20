<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7xpljjum.css';
import '../../css/w/wsh9lzbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m7xpljjum"/><path class="wsh9lzbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-drugs-cannabis" /></template>
