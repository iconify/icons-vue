<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary60mj0w.css';
import '../../css/f/fk-8gjbyw.css';
import '../../css/j/j14em3y7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ary60mj0w"/><path class="fk-8gjbyw"/><path class="j14em3y7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-snow-filled" /></template>
