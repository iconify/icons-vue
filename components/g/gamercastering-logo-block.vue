<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv8e7ibdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cv8e7ibdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gamercastering-logo-block" /></template>
