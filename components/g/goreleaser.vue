<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm0z6iaql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":391,"height":512};
const content = `<path class="tm0z6iaql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:goreleaser" /></template>
