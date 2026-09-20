<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6_er1b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6_er1b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:drupal-logo-2-block" /></template>
