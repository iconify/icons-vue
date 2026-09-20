<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-5aq062x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-5aq062x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flash-off" /></template>
