<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rshuo5wov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rshuo5wov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-dcos" /></template>
