<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp2m2nhck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xp2m2nhck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gitlab-full" /></template>
