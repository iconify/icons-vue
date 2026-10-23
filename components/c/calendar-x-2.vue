<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br0osbb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br0osbb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-x-2" /></template>
