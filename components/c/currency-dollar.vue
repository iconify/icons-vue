<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzn_xmbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzn_xmbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dollar" /></template>
