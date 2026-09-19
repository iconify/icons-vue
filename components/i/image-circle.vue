<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crens-u4t.css';
import '../../css/b/bwibdw4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crens-u4t"/><path class="bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-circle" /></template>
