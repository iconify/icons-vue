<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px8f0sm6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px8f0sm6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cashback-yen" /></template>
