<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgtbb6h2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgtbb6h2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-exclamation" /></template>
