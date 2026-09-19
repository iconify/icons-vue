<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm4e25hpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nm4e25hpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chess-board" /></template>
