<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbvqjyxk.css';
import '../../css/g/gyghflb6y.css';
import '../../css/j/j64dr1bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="bhbvqjyxk"/><path class="gyghflb6y"/><rect class="j64dr1bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layout-search-filled" /></template>
