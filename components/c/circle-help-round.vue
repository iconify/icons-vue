<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4lh6ebdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4lh6ebdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-help-round" /></template>
