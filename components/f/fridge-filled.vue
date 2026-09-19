<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phe-lywxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phe-lywxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fridge-filled" /></template>
