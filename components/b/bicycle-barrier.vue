<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm_kdvb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qm_kdvb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-barrier" /></template>
