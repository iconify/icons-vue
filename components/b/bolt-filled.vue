<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh5h3c62c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh5h3c62c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bolt-filled" /></template>
