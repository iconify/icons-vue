<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o86c79vyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o86c79vyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-search-outline" /></template>
