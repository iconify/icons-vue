<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jglg2ik2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jglg2ik2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-circle-right" /></template>
