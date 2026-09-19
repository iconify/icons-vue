<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfk4z3biw.css';
import '../../css/q/qi2aslb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfk4z3biw"/><path class="qi2aslb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-heart" /></template>
