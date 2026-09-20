<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usjkl6wdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usjkl6wdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-manat" /></template>
