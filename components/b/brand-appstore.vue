<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-pljsp1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-pljsp1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-appstore" /></template>
