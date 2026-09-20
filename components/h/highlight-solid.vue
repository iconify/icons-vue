<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkpy9cisa.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkpy9cisa"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:highlight-solid" /></template>
