<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt3s2tbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt3s2tbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jira-software-logo-1-block" /></template>
