<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwv58h7bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwv58h7bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:about-me-logo-solid" /></template>
