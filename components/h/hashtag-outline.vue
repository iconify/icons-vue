<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyz__6bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nyz__6bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hashtag-outline" /></template>
