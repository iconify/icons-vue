<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ri6bb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0ri6bb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:data-cloud-download" /></template>
