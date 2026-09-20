<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo1xnyukw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xo1xnyukw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:id-outline" /></template>
