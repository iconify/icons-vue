<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_s-0n7ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_s-0n7ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:broadcast-off" /></template>
