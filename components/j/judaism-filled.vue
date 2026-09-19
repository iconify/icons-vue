<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvfdbbfka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvfdbbfka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:judaism-filled" /></template>
