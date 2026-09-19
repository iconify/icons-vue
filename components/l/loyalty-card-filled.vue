<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih7o_lvei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih7o_lvei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:loyalty-card-filled" /></template>
