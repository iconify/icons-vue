<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fojs3xgit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fojs3xgit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:fullscreen" /></template>
