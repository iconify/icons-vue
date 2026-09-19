<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vps4jmb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vps4jmb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:computer-desktop-solid" /></template>
