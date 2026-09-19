<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oog5nub2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oog5nub2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:edit-03" /></template>
