<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd8wttb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8wttb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gumroad" /></template>
