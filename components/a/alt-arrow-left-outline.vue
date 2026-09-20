<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihzehbbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihzehbbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-outline" /></template>
