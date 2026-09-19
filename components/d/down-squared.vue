<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tny7lbc-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tny7lbc-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:down-squared" /></template>
