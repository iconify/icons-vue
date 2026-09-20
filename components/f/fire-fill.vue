<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvypdlbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvypdlbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:fire-fill" /></template>
