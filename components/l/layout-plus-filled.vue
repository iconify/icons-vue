<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbvqjyxk.css';
import '../../css/j/j64dr1bxs.css';
import '../../css/q/qpf972b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="bhbvqjyxk"/><rect class="j64dr1bxs"/><path class="qpf972b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layout-plus-filled" /></template>
