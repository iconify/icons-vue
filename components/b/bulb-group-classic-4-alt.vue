<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcq0-gbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcq0-gbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-4-alt" /></template>
