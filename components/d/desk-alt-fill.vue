<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7fle5b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7fle5b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:desk-alt-fill" /></template>
