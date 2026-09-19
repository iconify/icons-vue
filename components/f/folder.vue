<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd6hn1tbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd6hn1tbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:folder" /></template>
