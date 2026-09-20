<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr1zmubav.css';
import '../../css/k/kux3ecbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gr1zmubav"/><path class="kux3ecbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:caddy" /></template>
