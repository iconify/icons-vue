<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkji_-btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkji_-btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chromecast" /></template>
