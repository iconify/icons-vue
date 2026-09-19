<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie5rf59dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ie5rf59dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-left-16-solid" /></template>
