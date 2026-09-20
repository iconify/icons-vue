<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn_-277ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn_-277ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-reactivate" /></template>
