<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfuo44u9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfuo44u9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-down-filled" /></template>
