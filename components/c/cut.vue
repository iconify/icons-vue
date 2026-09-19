<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt-qzxb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":646};
const content = `<path class="mt-qzxb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:cut" /></template>
