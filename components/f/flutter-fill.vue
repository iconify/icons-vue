<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hswb42bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hswb42bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flutter-fill" /></template>
