<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtl2yqw5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qtl2yqw5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-down-small-solid" /></template>
