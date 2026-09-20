<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrx5gqidn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mrx5gqidn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fedora-logo-block" /></template>
