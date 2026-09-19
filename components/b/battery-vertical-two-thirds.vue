<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6cwkjbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6cwkjbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-vertical-two-thirds" /></template>
