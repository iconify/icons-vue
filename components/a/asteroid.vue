<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7o8pkuib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7o8pkuib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:asteroid" /></template>
