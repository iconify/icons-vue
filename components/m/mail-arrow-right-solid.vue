<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu2qk5bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu2qk5bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-arrow-right-solid" /></template>
