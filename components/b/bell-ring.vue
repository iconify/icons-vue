<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3vr93bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3vr93bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bell-ring" /></template>
