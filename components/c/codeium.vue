<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aieen2e4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aieen2e4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codeium" /></template>
