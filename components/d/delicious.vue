<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoleo-byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="eoleo-byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:delicious" /></template>
