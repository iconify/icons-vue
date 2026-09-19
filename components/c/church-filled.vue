<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxjc0_bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxjc0_bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:church-filled" /></template>
