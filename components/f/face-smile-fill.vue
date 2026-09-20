<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybn8519xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybn8519xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-smile-fill" /></template>
