<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytzz9x6wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytzz9x6wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cooking-pot-solid" /></template>
