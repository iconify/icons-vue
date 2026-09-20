<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caa9iac3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="caa9iac3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-right-sharp-fill" /></template>
