<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_15mh_uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":610,"height":700};
const content = `<path class="x_15mh_uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:ellipsis" /></template>
