<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2eqh8bvq.css';
import '../../css/o/o0t7-245s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2eqh8bvq"/><path class="o0t7-245s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bed-alt-filled" /></template>
