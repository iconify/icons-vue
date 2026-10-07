<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubm51gbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubm51gbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desklamp" /></template>
