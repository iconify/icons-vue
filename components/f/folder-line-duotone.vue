<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juolcjavn.css';
import '../../css/i/i4kly5b8q.css';
import '../../css/l/laly9hbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juolcjavn"/><path class="i4kly5b8q"/><path class="laly9hbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-line-duotone" /></template>
