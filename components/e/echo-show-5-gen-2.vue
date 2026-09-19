<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d90m7rm_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d90m7rm_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-show-5-gen-2" /></template>
