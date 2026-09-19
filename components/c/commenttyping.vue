<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2aumjbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n2aumjbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:commenttyping" /></template>
