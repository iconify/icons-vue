<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpi9_ac9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpi9_ac9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-trending-down-solid" /></template>
