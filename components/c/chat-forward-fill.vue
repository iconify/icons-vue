<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bymgqybfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bymgqybfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-forward-fill" /></template>
