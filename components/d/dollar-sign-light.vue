<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxpl77h-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxpl77h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:dollar-sign-light" /></template>
