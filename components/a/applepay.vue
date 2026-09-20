<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn77hbb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn77hbb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:applepay" /></template>
