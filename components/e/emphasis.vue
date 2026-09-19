<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brladpbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":730};
const content = `<path class="brladpbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:emphasis" /></template>
