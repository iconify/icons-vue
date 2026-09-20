<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kegl7dpms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kegl7dpms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kwai" /></template>
