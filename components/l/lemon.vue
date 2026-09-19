<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfi9oobug.css';
import '../../css/b/b_wglmqab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jfi9oobug"/><path class="b_wglmqab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:lemon" /></template>
