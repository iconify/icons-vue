<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc97kzb0z.css';
import '../../css/s/sgq67hbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mc97kzb0z"/><path class="sgq67hbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ice-cream-15" /></template>
