<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt6of_i9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt6of_i9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-minus-filled" /></template>
