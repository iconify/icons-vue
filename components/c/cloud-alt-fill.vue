<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i17tvmbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i17tvmbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:cloud-alt-fill" /></template>
