<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m02bcib0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m02bcib0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-plus-filled" /></template>
