<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9es34bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="k9es34bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:arrow-right" /></template>
