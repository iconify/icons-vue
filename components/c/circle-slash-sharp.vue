<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrk_5v7yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrk_5v7yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-slash-sharp" /></template>
