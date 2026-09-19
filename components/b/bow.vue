<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egb_ddg7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egb_ddg7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bow" /></template>
