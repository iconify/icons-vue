<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbvcw8bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rbvcw8bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-compare-outline" /></template>
