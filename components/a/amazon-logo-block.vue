<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wciun3xwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wciun3xwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amazon-logo-block" /></template>
