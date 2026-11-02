<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us4pzjbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us4pzjbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:archive-restore-line" /></template>
