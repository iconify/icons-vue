<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9-tsqbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a9-tsqbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-up-end-6" /></template>
