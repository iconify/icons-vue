<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k77di3nnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="k77di3nnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-tongue-wink" /></template>
