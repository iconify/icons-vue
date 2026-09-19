<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn_vi9bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sn_vi9bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chevrons-collapse-vertical-to-line" /></template>
