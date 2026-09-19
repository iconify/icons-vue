<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv0mj9bsl.css';
import '../../css/h/hmo75wbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="cv0mj9bsl"/><path class="hmo75wbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:camera-sharp" /></template>
