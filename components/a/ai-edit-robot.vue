<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-cjokb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-cjokb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-edit-robot" /></template>
