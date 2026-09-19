<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpcls9dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wcpcls9dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:grin-alt" /></template>
