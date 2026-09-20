<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bup0vabrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bup0vabrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x3" /></template>
