<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jykl4mcwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jykl4mcwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:eye-solid" /></template>
