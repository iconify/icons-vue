<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sro0m4o8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sro0m4o8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lemonsqueezy-filled" /></template>
