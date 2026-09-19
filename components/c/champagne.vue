<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvu27xjmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvu27xjmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:champagne" /></template>
