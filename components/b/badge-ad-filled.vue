<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evmgakbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evmgakbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-ad-filled" /></template>
