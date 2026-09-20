<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2qwrj83g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s2qwrj83g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:madagascar" /></template>
