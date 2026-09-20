<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4zslab_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4zslab_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-word" /></template>
