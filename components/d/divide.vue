<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lit4pnbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="lit4pnbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:divide" /></template>
