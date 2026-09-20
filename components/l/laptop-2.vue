<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ffcxrtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_ffcxrtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:laptop-2" /></template>
