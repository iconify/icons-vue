<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc_3y57dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc_3y57dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-2" /></template>
