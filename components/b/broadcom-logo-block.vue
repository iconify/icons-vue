<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2exkg4dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2exkg4dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:broadcom-logo-block" /></template>
