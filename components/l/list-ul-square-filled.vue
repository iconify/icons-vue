<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daapk0d1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daapk0d1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-ul-square-filled" /></template>
