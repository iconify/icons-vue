<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suf1grbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suf1grbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:info-octagon-filled" /></template>
