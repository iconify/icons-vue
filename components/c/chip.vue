<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s99ga2boz.css';
import '../../css/m/maw0v5bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer s99ga2boz"/><path class="duoicon-primary-layer maw0v5bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:chip" /></template>
