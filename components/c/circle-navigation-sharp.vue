<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvtt6wbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvtt6wbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-navigation-sharp" /></template>
