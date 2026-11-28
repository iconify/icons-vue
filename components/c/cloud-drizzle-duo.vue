<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6kfekqvf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ob67c_b2q.css';
import '../../css/s/sb6huacei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6kfekqvf secondary"/><g class="dt0cm9dhy primary"><path class="ob67c_b2q"/><path class="sb6huacei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-drizzle-duo" /></template>
