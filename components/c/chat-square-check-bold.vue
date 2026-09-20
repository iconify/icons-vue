<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnt4fyv0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnt4fyv0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-check-bold" /></template>
