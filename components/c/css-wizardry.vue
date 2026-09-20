<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pflvn04nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pflvn04nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:css-wizardry" /></template>
