<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2082-6zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2082-6zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-question" /></template>
