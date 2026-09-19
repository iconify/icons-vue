<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/actikbcpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="actikbcpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:linkedin2" /></template>
