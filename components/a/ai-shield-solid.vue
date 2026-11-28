<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsxcxqbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxcxqbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-shield-solid" /></template>
