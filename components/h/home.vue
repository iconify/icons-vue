<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbt61yhpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbt61yhpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:home" /></template>
