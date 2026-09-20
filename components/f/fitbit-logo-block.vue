<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nam5eh0cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nam5eh0cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fitbit-logo-block" /></template>
