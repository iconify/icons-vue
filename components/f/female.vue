<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx5brxb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gx5brxb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:female" /></template>
