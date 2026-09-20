<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oly-ng79r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oly-ng79r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:apm" /></template>
