<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa309cbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa309cbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlemybusiness" /></template>
