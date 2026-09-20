<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yef1ulbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yef1ulbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:alert-bell-notification-2" /></template>
