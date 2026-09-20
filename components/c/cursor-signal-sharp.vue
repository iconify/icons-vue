<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6fqr2b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6fqr2b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-signal-sharp" /></template>
