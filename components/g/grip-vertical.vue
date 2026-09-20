<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms-gnf8qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms-gnf8qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grip-vertical" /></template>
