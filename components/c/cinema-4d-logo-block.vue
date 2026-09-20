<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/impvs4byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="impvs4byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cinema-4d-logo-block" /></template>
