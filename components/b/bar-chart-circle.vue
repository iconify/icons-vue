<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evx3bqa7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="evx3bqa7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-chart-circle" /></template>
