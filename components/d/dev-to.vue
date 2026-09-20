<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2e_s8ywe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2e_s8ywe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dev-to" /></template>
