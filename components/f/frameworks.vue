<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp41u6b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp41u6b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:frameworks" /></template>
