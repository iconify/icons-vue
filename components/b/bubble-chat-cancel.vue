<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxhfssews.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxhfssews"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-cancel" /></template>
