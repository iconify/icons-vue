<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsetkrwdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsetkrwdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-left-right" /></template>
