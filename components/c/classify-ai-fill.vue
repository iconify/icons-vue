<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7uw_y9fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7uw_y9fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-ai-fill" /></template>
