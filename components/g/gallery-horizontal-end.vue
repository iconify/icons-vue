<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8zzqebrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8zzqebrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gallery-horizontal-end" /></template>
