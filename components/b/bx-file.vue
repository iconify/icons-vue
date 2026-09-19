<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8wp0nbtd.css';
import '../../css/m/m5ioxlbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8wp0nbtd"/><path class="m5ioxlbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-file" /></template>
