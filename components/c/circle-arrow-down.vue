<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yltk3ebdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yltk3ebdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-down" /></template>
