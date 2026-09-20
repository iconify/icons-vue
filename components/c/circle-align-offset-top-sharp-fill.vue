<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htw7-ymao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htw7-ymao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-top-sharp-fill" /></template>
