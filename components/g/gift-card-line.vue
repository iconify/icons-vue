<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkn6_o_df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkn6_o_df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-card-line" /></template>
