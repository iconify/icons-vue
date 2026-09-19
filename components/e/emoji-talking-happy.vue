<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icffncbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icffncbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:emoji-talking-happy" /></template>
