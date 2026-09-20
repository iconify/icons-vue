<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve6-hobta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6-hobta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-code-sharp" /></template>
