<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etwiq-3gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="etwiq-3gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-up" /></template>
