<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiycpfkrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iiycpfkrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:line-solid" /></template>
