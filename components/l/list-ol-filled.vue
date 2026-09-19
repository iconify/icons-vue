<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz45510ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz45510ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-ol-filled" /></template>
