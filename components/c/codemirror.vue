<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thqu2k3qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thqu2k3qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codemirror" /></template>
