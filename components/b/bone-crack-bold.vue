<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avz4_kb7i.css';
import '../../css/b/b2_20abta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avz4_kb7i"/><path class="b2_20abta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-crack-bold" /></template>
