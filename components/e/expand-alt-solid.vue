<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz_vj9-yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jz_vj9-yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:expand-alt-solid" /></template>
