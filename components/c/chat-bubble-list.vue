<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttczh_67h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttczh_67h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-list" /></template>
