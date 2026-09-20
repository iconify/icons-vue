<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8qo20b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8qo20b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-bubble" /></template>
