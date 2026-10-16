<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie4p76ois.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":310,"height":310};
const content = `<path class="ie4p76ois"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cockpit-cms-light" /></template>
