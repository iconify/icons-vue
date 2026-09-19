<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoc66lyzr.css';
import '../../css/p/p4gdroa5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoc66lyzr"/><path class="p4gdroa5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bus" /></template>
