<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa_hafb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qa_hafb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:like-1-solid" /></template>
