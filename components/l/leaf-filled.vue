<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueksp0b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueksp0b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:leaf-filled" /></template>
