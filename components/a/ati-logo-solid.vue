<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awp4qobzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awp4qobzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ati-logo-solid" /></template>
