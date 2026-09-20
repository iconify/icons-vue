<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_-885d7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_-885d7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-filled" /></template>
