<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-0itp1as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-0itp1as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:code-minus" /></template>
