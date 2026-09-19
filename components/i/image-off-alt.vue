<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxejc3bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxejc3bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-off-alt" /></template>
