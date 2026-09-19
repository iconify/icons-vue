<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhkv8stfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhkv8stfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:camera-person" /></template>
