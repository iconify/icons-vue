<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7bptcchk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7bptcchk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-right-lines" /></template>
