<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r01s9xbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r01s9xbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:layout-fill" /></template>
