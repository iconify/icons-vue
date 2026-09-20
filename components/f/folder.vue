<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eydn-4nyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eydn-4nyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:folder" /></template>
