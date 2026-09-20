<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq6l3ibbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq6l3ibbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:acala" /></template>
