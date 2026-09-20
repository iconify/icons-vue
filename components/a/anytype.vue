<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd5f-k6hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd5f-k6hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:anytype" /></template>
