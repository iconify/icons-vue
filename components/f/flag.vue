<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7u5d87up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="b7u5d87up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:flag" /></template>
