<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8gc-8b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="a8gc-8b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:eject" /></template>
