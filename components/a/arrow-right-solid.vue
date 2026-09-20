<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nooz18b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nooz18b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-right-solid" /></template>
