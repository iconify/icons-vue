<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8k9kvo-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x8k9kvo-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:animal-shelter" /></template>
