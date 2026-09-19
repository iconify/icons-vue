<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p14n-8bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p14n-8bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:briefcase" /></template>
