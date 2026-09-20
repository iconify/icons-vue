<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brwgglt3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="brwgglt3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-pound" /></template>
