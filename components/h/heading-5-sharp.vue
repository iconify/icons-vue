<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f540g9cop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f540g9cop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-5-sharp" /></template>
