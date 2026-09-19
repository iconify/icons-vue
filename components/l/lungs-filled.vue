<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq5_qinww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq5_qinww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lungs-filled" /></template>
