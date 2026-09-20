<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyy782h9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyy782h9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adobelightroomclassic" /></template>
