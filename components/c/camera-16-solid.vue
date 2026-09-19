<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nye6a6pnu.css';
import '../../css/j/jez9isbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nye6a6pnu"/><path clip-rule="evenodd" class="jez9isbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:camera-16-solid" /></template>
