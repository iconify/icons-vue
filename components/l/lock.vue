<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6da6xbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6da6xbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lock" /></template>
