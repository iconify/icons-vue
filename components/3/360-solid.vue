<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axq885ryf.css';
import '../../css/f/fegcs2boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="axq885ryf"/><path clip-rule="evenodd" class="fegcs2boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:360-solid" /></template>
