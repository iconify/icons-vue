<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_tkm_8we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k_tkm_8we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cairn-beside-trail-blazes-right" /></template>
