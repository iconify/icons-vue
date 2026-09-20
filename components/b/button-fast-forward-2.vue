<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohne5abyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohne5abyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:button-fast-forward-2" /></template>
