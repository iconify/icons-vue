<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3zgc2n5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="n3zgc2n5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:lightnings" /></template>
