<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml0qwybrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ml0qwybrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-minus-solid" /></template>
