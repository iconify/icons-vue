<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilp137j6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilp137j6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:club-filled" /></template>
