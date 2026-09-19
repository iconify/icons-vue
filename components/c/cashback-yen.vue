<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9uro8i1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9uro8i1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cashback-yen" /></template>
