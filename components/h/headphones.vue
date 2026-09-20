<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6kfg4k8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6kfg4k8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:headphones" /></template>
