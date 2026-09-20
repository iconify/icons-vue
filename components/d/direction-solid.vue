<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbncg7bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rbncg7bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:direction-solid" /></template>
