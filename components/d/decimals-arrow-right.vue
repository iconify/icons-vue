<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o332-_lfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o332-_lfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:decimals-arrow-right" /></template>
