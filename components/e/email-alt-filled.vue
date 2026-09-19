<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmth8o4lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmth8o4lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-alt-filled" /></template>
