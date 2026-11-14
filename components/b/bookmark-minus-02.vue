<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3wj9339p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3wj9339p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-minus-02" /></template>
