<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibh0pxv3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibh0pxv3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:badge-solid" /></template>
