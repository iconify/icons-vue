<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_7cubbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_7cubbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-check" /></template>
