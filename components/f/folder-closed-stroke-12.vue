<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuwsj3zho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uuwsj3zho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folder-closed-stroke-12" /></template>
