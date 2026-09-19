<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj7eyqd0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj7eyqd0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cup-hot" /></template>
