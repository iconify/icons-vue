<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg0pcrbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg0pcrbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-right-arrow-circle" /></template>
