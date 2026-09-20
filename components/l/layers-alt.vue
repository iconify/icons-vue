<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2eb48dil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2eb48dil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:layers-alt" /></template>
