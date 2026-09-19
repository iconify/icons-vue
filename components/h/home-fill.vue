<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8bf7_9ae.css';
import '../../css/w/wmc2ozbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8bf7_9ae"/><path class="wmc2ozbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:home-fill" /></template>
