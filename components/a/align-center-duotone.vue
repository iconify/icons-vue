<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w123mzbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w123mzbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:align-center-duotone" /></template>
