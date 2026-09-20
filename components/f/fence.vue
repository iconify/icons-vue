<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi0g_w8en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi0g_w8en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:fence" /></template>
