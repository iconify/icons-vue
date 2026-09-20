<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci77r-bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ci77r-bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:denied-solid" /></template>
