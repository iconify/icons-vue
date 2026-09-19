<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd6q1996p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd6q1996p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:block-filled" /></template>
