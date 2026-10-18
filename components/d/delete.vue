<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvlzv7ffg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvlzv7ffg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:delete" /></template>
