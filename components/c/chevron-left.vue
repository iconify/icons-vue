<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q706zcc7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q706zcc7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:chevron-left" /></template>
