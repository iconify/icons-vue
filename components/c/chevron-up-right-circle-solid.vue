<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e50ri4bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e50ri4bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-right-circle-solid" /></template>
