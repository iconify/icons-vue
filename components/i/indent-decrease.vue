<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3eo08bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x3eo08bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:indent-decrease" /></template>
