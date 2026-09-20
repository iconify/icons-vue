<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_6rk7bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_6rk7bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-right" /></template>
