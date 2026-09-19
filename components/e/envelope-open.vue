<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvjy63bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nvjy63bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:envelope-open" /></template>
