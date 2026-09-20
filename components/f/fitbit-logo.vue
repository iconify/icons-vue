<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zueh1cegf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zueh1cegf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:fitbit-logo" /></template>
