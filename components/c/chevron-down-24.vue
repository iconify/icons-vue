<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi_pi4bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi_pi4bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-down-24" /></template>
