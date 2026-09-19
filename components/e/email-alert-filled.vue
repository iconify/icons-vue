<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8o11-toh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8o11-toh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-alert-filled" /></template>
