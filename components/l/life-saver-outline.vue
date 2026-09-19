<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbs_ywbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbs_ywbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:life-saver-outline" /></template>
