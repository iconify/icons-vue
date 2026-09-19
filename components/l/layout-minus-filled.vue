<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbvqjyxk.css';
import '../../css/j/j64dr1bxs.css';
import '../../css/b/bba041bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="bhbvqjyxk"/><rect class="j64dr1bxs"/><path class="bba041bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layout-minus-filled" /></template>
