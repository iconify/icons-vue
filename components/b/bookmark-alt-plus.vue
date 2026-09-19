<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr6ielglk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr6ielglk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bookmark-alt-plus" /></template>
