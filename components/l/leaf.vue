<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reyt_ebqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="reyt_ebqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:leaf" /></template>
