<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4qqhxadq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4qqhxadq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:diff-modified" /></template>
