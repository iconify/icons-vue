<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x67kqwb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x67kqwb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:corona-renderer" /></template>
