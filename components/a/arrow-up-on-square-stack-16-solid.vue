<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juq_70b2e.css';
import '../../css/b/b48fucctu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="juq_70b2e"/><path class="b48fucctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-on-square-stack-16-solid" /></template>
