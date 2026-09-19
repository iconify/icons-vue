<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqz-ogqhl.css';
import '../../css/a/a2nfcgrow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="eqz-ogqhl"/><path class="a2nfcgrow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ca-4x3" /></template>
