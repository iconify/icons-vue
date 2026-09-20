<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh693iuzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh693iuzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-eye" /></template>
