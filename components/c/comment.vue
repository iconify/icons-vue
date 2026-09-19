<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_n19kbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t_n19kbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:comment" /></template>
