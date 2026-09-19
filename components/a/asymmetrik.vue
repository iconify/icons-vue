<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h133c6uhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h133c6uhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:asymmetrik" /></template>
