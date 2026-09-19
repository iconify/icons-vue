<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv8gugehk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv8gugehk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-show-8-group" /></template>
