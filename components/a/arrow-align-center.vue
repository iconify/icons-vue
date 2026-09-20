<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/h/hzcqba.css';
import '../../css/s/sbei0c.css';
import '../../css/g/gvulyl.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hzcqba"/><path class="a0m25c sbei0c"/><path class="a0m25c gvulyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-align-center" /></template>
