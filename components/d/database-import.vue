<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp55kxb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pp55kxb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:database-import" /></template>
