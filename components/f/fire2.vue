<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gra77-eol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gra77-eol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fire2" /></template>
