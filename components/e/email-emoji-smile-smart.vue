<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqpbdh_ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mqpbdh_ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-emoji-smile-smart" /></template>
