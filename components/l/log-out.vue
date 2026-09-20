<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/y/yo13rm.css';
import '../../css/w/w90myk.css';
import '../../css/v/vusf7y.css';
import '../../css/s/so-from-46.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c yo13rm"/><path class="a0m25c w90myk"/><path class="a0m25c vusf7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:log-out" /></template>
