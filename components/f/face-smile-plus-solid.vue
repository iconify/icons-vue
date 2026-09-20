<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upyut0o1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upyut0o1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-smile-plus-solid" /></template>
