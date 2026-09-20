<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzws48i-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="gzws48i-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-tick-solid" /></template>
