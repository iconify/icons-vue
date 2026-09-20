<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9dpl7yvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9dpl7yvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bebo-logo-solid" /></template>
