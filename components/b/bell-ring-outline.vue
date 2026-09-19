<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al0-lwb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al0-lwb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bell-ring-outline" /></template>
