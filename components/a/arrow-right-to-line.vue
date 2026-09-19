<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnl-5nbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lnl-5nbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-right-to-line" /></template>
