<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rve9bjm7q.css';
import '../../css/w/wtuwfnr6g.css';
import '../../css/i/isltlb-7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rve9bjm7q"/><path class="wtuwfnr6g"/><path clip-rule="evenodd" class="isltlb-7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-recive-bold" /></template>
