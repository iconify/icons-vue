<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om-zcd1ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om-zcd1ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-google" /></template>
