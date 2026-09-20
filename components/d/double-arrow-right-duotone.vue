<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3qg_u9su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3qg_u9su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:double-arrow-right-duotone" /></template>
