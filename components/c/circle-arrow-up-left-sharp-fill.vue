<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h29zzibek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h29zzibek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-up-left-sharp-fill" /></template>
