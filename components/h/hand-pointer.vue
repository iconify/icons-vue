<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9bht_bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x9bht_bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-pointer" /></template>
