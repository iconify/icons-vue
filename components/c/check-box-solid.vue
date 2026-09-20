<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vafs9rb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vafs9rb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-box-solid" /></template>
