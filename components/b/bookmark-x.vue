<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbez4kq0u.css';
import '../../css/g/gfk4z3biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbez4kq0u"/><path class="gfk4z3biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-x" /></template>
