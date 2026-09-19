<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yox6y9bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yox6y9bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:angry2" /></template>
