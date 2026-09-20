<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b56-y7bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b56-y7bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:branch-up-filled" /></template>
