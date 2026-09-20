<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhlg9b33u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rhlg9b33u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drag-solid" /></template>
