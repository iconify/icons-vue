<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocwumyh_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocwumyh_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hierarchy-16-solid" /></template>
