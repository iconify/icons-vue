<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un4-q6b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un4-q6b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-circle-bold" /></template>
