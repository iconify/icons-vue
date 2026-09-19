<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6nbuubyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="a6nbuubyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:database" /></template>
