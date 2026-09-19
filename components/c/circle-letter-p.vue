<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph-t_0mkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ph-t_0mkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-p" /></template>
