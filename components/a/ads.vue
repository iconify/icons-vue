<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieuuixy1o.css';
import '../../css/m/m1si3hbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieuuixy1o"/><path class="m1si3hbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ads" /></template>
