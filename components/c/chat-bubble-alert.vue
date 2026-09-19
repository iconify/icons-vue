<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo6v9hk9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo6v9hk9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-alert" /></template>
