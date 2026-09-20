<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9igarvzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n9igarvzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-minus-outline" /></template>
