<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oht4ataxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oht4ataxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:handshake" /></template>
