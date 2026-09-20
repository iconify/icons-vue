<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1p9s6bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="o1p9s6bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:divider-line-solid" /></template>
