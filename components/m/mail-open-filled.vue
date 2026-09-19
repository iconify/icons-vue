<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1nkkbbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1nkkbbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mail-open-filled" /></template>
