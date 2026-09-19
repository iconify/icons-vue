<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn9b5bcba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":512};
const content = `<path class="vn9b5bcba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-user" /></template>
