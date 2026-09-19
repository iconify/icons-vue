<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_jkadc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_jkadc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:closed-captions-tag-solid" /></template>
