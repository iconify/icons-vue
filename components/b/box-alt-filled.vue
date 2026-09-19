<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_8drnl1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_8drnl1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:box-alt-filled" /></template>
