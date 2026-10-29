<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgdziki5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgdziki5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brain-cog" /></template>
