<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdtr37oeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kdtr37oeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:indent-increase-outline" /></template>
