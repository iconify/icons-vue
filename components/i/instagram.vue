<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2uer03cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x2uer03cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:instagram" /></template>
