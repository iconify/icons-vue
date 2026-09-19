<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8uf12bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8uf12bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:contrast" /></template>
