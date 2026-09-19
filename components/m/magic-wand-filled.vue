<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xea5qkezm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xea5qkezm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:magic-wand-filled" /></template>
