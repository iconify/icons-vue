<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjel4zbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjel4zbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bookmark" /></template>
