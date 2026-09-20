<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o24enpbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o24enpbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-check-fill" /></template>
