<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0-xzpt5k.css';
import '../../css/n/nrqatuf6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer p0-xzpt5k"/><path class="duoicon-secondary-layer nrqatuf6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:cloud-lightning" /></template>
