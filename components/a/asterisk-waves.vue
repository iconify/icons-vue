<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu0ax1bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu0ax1bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-waves" /></template>
