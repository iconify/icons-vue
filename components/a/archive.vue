<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzeam0brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzeam0brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:archive" /></template>
