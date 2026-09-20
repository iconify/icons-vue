<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee65k1lyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee65k1lyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-arrow-right-light" /></template>
