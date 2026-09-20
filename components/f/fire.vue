<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwtwn7bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwtwn7bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:fire" /></template>
