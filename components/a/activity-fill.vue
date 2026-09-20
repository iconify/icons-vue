<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svrehyewm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svrehyewm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:activity-fill" /></template>
