<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0tn9tb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0tn9tb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:button" /></template>
