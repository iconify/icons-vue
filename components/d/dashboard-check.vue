<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw08v2bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw08v2bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-check" /></template>
