<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2fpl2orn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2fpl2orn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-minus-bold" /></template>
