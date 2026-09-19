<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4hngr2zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4hngr2zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:device-tablet" /></template>
