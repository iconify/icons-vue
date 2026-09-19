<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ljzfb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t8ljzfb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:hangouts" /></template>
