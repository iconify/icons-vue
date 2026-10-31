<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f61xg1bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f61xg1bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie-solid" /></template>
