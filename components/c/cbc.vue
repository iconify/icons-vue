<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsqy12cmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsqy12cmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cbc" /></template>
