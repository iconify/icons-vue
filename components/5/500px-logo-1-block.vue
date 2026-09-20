<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ato2_p4nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ato2_p4nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:500px-logo-1-block" /></template>
