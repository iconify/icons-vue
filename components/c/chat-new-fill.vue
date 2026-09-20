<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nua2v_4eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nua2v_4eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-new-fill" /></template>
