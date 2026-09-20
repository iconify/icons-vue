<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z32njrjms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z32njrjms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amcrest-light" /></template>
