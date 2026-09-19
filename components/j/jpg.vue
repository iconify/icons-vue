<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpg420nlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpg420nlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:jpg" /></template>
