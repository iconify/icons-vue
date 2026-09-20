<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pex4nmbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pex4nmbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:atlassian-logo-block" /></template>
