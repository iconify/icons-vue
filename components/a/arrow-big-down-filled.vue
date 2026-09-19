<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7nzfkbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7nzfkbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-down-filled" /></template>
