<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daws0z85g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daws0z85g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:affiliate" /></template>
