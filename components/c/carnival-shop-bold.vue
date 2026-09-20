<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mso_j6xqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mso_j6xqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:carnival-shop-bold" /></template>
