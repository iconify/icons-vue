<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kppq0fbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kppq0fbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:audio-technica" /></template>
