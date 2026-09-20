<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rty2h_9ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rty2h_9ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-dead-fill" /></template>
