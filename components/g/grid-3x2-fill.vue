<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9zwy09dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9zwy09dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-3x2-fill" /></template>
