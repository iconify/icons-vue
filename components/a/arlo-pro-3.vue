<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylgsnlw_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylgsnlw_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-pro-3" /></template>
