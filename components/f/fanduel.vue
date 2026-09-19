<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze0rifjjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze0rifjjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fanduel" /></template>
