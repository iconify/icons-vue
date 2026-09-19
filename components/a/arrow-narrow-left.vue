<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5umild4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5umild4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-narrow-left" /></template>
