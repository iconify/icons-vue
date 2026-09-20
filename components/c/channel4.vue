<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl09u1b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl09u1b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:channel4" /></template>
