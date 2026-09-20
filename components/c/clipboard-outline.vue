<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0wdx9ywn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v0wdx9ywn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-outline" /></template>
