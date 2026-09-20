<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1uf_1b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":43,"left":-0.835,"top":-0.509};
const content = `<path clip-rule="evenodd" class="f1uf_1b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:astrazeneca" /></template>
