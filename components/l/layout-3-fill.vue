<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq5mre2ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq5mre2ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-3-fill" /></template>
