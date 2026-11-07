<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt0ievjnc.css';
import '../../css/n/nazq8_bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0ievjnc"/><path class="nazq8_bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-bold" /></template>
