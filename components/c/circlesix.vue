<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1tw9_spv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k1tw9_spv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlesix" /></template>
