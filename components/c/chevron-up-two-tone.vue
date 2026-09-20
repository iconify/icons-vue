<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veyfuxbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veyfuxbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-up-two-tone" /></template>
