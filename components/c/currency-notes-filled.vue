<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rojie2byc.css';
import '../../css/z/zooty4bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rojie2byc"/><path class="zooty4bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:currency-notes-filled" /></template>
