<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vim6mcbhb.css';
import '../../css/h/hndh_kb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vim6mcbhb"/><path clip-rule="evenodd" class="hndh_kb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:android-outline" /></template>
