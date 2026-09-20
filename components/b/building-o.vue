<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayfjvlbde.css';
import '../../css/p/pb95qppxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ayfjvlbde"/><path class="pb95qppxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:building-o" /></template>
