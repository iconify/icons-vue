<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhjwkd_5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhjwkd_5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-center-filled" /></template>
