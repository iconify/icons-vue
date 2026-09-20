<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h654y7b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h654y7b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:evernote-logo-block" /></template>
