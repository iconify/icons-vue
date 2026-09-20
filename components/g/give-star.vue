<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buc-j7b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="buc-j7b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:give-star" /></template>
