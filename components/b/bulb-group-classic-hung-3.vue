<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxko29b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxko29b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-hung-3" /></template>
