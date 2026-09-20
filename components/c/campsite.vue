<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnseyubee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lnseyubee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite" /></template>
