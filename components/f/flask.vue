<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffb0y8qbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffb0y8qbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:flask" /></template>
