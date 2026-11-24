<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary60mj0w.css';
import '../../css/p/pm4uhbk1b.css';
import '../../css/j/j14em3y7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ary60mj0w"/><path class="pm4uhbk1b"/><path class="j14em3y7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-snow-filled" /></template>
