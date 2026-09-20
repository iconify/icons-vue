<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkftz_bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkftz_bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:focus-auto-1" /></template>
