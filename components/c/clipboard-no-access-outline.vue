<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq5r37b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rq5r37b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-no-access-outline" /></template>
