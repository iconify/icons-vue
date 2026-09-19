<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pps9wib3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pps9wib3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:files-filled" /></template>
