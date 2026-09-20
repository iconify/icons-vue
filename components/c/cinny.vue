<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifkswpb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifkswpb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cinny" /></template>
