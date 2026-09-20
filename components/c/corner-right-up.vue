<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjrx52b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjrx52b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-right-up" /></template>
