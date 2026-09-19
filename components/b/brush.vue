<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm7_4jbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm7_4jbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:brush" /></template>
