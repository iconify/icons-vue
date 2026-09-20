<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k__9mgudr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k__9mgudr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bento" /></template>
