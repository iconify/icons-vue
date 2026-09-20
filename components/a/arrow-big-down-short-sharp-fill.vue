<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nws4xlbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nws4xlbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-down-short-sharp-fill" /></template>
