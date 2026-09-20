<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iypj7136t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iypj7136t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coughing-face" /></template>
