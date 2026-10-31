<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfm_2l7uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfm_2l7uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-down-duotone-round" /></template>
