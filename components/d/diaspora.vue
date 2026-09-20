<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdnr9q_oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdnr9q_oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:diaspora" /></template>
