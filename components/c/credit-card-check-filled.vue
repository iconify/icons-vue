<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk9e7vb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dk9e7vb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-check-filled" /></template>
