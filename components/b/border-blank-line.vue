<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-rcih6-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-rcih6-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-blank-line" /></template>
