<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa0q_wbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="xa0q_wbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:beer" /></template>
