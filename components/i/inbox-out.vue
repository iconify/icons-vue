<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v70d_-yfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v70d_-yfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:inbox-out" /></template>
