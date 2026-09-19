<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2i6v5hdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2i6v5hdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-off-02" /></template>
