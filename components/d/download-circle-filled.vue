<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkclmjbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkclmjbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:download-circle-filled" /></template>
