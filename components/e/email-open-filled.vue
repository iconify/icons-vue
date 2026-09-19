<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycz-ohbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ycz-ohbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-open-filled" /></template>
