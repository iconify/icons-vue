<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz2byabdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="nz2byabdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cassette" /></template>
