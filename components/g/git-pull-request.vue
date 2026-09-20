<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mulav-akh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mulav-akh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request" /></template>
