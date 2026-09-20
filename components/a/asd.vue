<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4fwx8bcd.css';
import '../../css/k/kp9tsokzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4fwx8bcd"/><path class="kp9tsokzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:asd" /></template>
