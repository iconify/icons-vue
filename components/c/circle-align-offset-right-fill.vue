<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6uppcwnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6uppcwnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-right-fill" /></template>
