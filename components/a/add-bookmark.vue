<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye9nqmbve.css';
import '../../css/w/wo2kix3uq.css';
import '../../css/i/ijwz2bbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ye9nqmbve"/><path class="wo2kix3uq"/><path class="ijwz2bbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:add-bookmark" /></template>
