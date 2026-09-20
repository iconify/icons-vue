<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_oorg.css';
import '../../css/i/iw1iew.css';
import '../../css/s/sjhm0t.css';
import '../../css/s/so-from-64.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_oorg iw1iew"/><path class="iw1iew sjhm0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:briefcase-filled" /></template>
