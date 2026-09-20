<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ues9upbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ues9upbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-add-bold" /></template>
