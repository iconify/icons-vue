<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge6e27bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge6e27bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jira-software-logo-1-solid" /></template>
