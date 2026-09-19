<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bebt1abvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bebt1abvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:coffee" /></template>
