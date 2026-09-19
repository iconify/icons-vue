<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmy9m9bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmy9m9bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-add-bold" /></template>
