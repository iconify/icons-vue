<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7_7-h00t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7_7-h00t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:leafs" /></template>
