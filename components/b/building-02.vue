<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n22q7k0rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n22q7k0rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:building-02" /></template>
