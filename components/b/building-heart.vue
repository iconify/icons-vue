<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dckcdhsls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dckcdhsls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-heart" /></template>
