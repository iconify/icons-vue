<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqo7-v_cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqo7-v_cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart2" /></template>
