<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plk8nejnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plk8nejnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-down" /></template>
