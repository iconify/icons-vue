<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-6pfdc6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6pfdc6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:laptop-upload" /></template>
