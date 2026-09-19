<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_4soybfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_4soybfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:expand-outline" /></template>
