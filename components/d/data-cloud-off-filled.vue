<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wky75f0nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wky75f0nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:data-cloud-off-filled" /></template>
