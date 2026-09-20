<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_u6k5bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_u6k5bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-letter-case-lower" /></template>
