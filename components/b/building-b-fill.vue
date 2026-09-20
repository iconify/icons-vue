<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv6ul_bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv6ul_bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:building-b-fill" /></template>
