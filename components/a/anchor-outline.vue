<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npr3txk6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="npr3txk6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:anchor-outline" /></template>
