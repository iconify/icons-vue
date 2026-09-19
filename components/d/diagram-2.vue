<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmj6onr3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kmj6onr3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:diagram-2" /></template>
