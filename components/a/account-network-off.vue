<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dndr5xb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dndr5xb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-network-off" /></template>
