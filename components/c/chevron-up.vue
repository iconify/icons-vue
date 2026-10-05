<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjtqf-b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjtqf-b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:chevron-up" /></template>
