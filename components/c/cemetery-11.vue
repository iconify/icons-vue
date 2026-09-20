<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztnzy1bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ztnzy1bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cemetery-11" /></template>
