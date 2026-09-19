<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk3cyc-gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":488};
const content = `<path class="yk3cyc-gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:gdgt" /></template>
