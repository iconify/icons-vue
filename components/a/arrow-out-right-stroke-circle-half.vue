<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edesw8bbn.css';
import '../../css/p/p7k_3ybxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edesw8bbn"/><path class="p7k_3ybxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-right-stroke-circle-half" /></template>
