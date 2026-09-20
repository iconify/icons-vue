<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp-vnccpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tp-vnccpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:approval" /></template>
