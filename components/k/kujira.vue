<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy7nfem9n.css';
import '../../css/w/wgkp86hhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy7nfem9n"/><path class="wgkp86hhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kujira" /></template>
