<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcu911z9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcu911z9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:jar-plus" /></template>
