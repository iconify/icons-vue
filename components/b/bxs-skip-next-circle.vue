<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9eql_-9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9eql_-9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-skip-next-circle" /></template>
