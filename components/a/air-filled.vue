<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w72f55b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w72f55b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:air-filled" /></template>
