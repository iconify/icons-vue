<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3y-c2bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3y-c2bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:log-in" /></template>
