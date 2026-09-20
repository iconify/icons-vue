<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1pe50bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1pe50bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:alert-octagon-1-bold" /></template>
