<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbrxq9bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qbrxq9bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:disable-bell-notification-solid" /></template>
