<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib_4_u6ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ib_4_u6ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:flickr3" /></template>
