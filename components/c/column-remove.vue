<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5fog1mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5fog1mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:column-remove" /></template>
