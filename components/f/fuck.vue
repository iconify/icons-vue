<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px4ty5bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":472};
const content = `<path class="px4ty5bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:fuck" /></template>
