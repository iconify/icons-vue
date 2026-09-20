<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip_2e3jip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip_2e3jip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eurs" /></template>
