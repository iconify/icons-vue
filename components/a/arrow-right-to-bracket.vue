<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewg_2oqwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ewg_2oqwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-right-to-bracket" /></template>
