<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffcyl_qct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffcyl_qct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrange-list" /></template>
