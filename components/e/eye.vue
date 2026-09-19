<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei5v8ab1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ei5v8ab1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:eye" /></template>
