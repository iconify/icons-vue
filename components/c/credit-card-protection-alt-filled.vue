<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3x49bb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3x49bb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-protection-alt-filled" /></template>
