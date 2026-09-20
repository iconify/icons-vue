<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyatf7whr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyatf7whr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-outline" /></template>
