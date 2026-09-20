<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcsw2jb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="wcsw2jb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:egg-f" /></template>
