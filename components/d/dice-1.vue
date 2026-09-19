<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkczs_bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkczs_bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dice-1" /></template>
