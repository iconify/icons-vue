<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvxwe6h2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxwe6h2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-solid" /></template>
