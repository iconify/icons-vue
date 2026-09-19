<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7z0agbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7z0agbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:grid-02" /></template>
