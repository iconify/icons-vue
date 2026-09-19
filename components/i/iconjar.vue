<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4v76nb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4v76nb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:iconjar" /></template>
