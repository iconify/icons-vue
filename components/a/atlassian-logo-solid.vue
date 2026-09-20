<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk1l1r10t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk1l1r10t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:atlassian-logo-solid" /></template>
