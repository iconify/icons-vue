<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecxct7tly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecxct7tly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:claris" /></template>
