<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oum0u3bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oum0u3bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-left-right-filled" /></template>
