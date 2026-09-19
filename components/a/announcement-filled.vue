<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w635a-b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w635a-b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:announcement-filled" /></template>
