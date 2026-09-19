<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba_94wemm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba_94wemm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-2-duotone" /></template>
