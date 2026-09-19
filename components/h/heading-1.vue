<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu641e4zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu641e4zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heading-1" /></template>
