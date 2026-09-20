<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc4n_nfpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wc4n_nfpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:level-up" /></template>
