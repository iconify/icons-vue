<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk3rxbbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk3rxbbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bell-notification-square-fill" /></template>
