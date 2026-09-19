<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syghy1b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syghy1b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-ul-filled" /></template>
