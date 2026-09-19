<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut_kj5bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ut_kj5bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:feather-alt" /></template>
