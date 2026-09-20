<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntp499brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntp499brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:keyboard-off" /></template>
