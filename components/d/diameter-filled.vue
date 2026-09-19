<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb-_29axf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb-_29axf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:diameter-filled" /></template>
