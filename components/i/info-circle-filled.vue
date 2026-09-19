<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fren9q4hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fren9q4hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:info-circle-filled" /></template>
