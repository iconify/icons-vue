<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r__f3wn0s.css';
import '../../css/t/tpa5nbb8v.css';
import '../../css/l/lcnzvy4sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r__f3wn0s"/><path class="tpa5nbb8v"/><path class="lcnzvy4sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-open-bold-duotone" /></template>
