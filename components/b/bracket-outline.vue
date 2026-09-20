<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6k0cjx2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d6k0cjx2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bracket-outline" /></template>
