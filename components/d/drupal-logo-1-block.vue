<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5wn4bbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5wn4bbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:drupal-logo-1-block" /></template>
