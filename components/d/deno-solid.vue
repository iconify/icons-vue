<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao7jv8aag.css';
import '../../css/o/ouxiombbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ao7jv8aag"/><path clip-rule="evenodd" class="ouxiombbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:deno-solid" /></template>
