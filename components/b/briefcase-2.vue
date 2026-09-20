<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntsye-bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntsye-bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:briefcase-2" /></template>
