<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp2l6s40o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2l6s40o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-square" /></template>
