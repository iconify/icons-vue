<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft1d7lbyz.css';
import '../../css/w/w2fc8uq2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft1d7lbyz"/><path class="w2fc8uq2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cycling-filled" /></template>
