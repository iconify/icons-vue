<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk4-s9iov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk4-s9iov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:emergency-call-remix" /></template>
