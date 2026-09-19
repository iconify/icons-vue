<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvu0d3bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvu0d3bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-show-8-gen-2" /></template>
