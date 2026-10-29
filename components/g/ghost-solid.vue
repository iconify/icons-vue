<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv32cqbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv32cqbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ghost-solid" /></template>
