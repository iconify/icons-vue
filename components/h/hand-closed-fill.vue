<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4296odcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m4296odcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-closed-fill" /></template>
