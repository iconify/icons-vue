<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5oho7a5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k5oho7a5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-horizontal-alt-outline" /></template>
