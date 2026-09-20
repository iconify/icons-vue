<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp6l9nbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":32};
const content = `<path class="jp6l9nbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bonusly" /></template>
