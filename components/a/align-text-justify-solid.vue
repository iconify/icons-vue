<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k90ezdbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="k90ezdbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-justify-solid" /></template>
