<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okl-q-bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okl-q-bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-plus-filled" /></template>
