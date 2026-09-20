<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljc6226xi.css';
import '../../css/u/uqoy3wbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljc6226xi"/><path class="uqoy3wbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-lending" /></template>
