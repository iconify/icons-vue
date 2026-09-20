<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt5d2i_le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt5d2i_le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-flutter" /></template>
