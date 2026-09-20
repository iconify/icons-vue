<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0mzb2gdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0mzb2gdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brackets" /></template>
