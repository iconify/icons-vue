<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f47fbkbfi.css';
import '../../css/z/z8ew59bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f47fbkbfi"/><path class="z8ew59bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:bell-duotone" /></template>
