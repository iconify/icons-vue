<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwznp_2kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwznp_2kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-stackshare" /></template>
