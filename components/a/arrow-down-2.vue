<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_zndpbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zndpbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-down-2" /></template>
