<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt8pr1bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt8pr1bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevron-last" /></template>
