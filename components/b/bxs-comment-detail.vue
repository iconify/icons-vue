<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiqhgmb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiqhgmb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-comment-detail" /></template>
