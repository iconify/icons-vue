<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prnpfqb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prnpfqb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookorbit-dark" /></template>
