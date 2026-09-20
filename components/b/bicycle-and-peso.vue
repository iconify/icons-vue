<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi_scccbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qi_scccbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-peso" /></template>
