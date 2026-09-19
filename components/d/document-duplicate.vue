<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9isj2bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9isj2bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-duplicate" /></template>
