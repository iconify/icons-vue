<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-922rvxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="b-922rvxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-circle-o-up" /></template>
