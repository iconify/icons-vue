<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf6vjib6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf6vjib6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:codecov-logo-solid" /></template>
