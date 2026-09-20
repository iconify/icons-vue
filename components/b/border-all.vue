<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apca3-bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="apca3-bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:border-all" /></template>
