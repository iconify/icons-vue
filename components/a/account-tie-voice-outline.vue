<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghi7qny3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghi7qny3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-tie-voice-outline" /></template>
