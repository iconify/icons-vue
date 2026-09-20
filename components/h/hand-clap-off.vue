<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwszk5ntc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwszk5ntc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-clap-off" /></template>
