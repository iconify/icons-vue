<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvf-84bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nvf-84bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-happy-stroke-12" /></template>
