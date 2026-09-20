<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijz0xvbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijz0xvbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones3-filled" /></template>
