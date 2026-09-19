<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7dmfabjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7dmfabjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevron-down-fill" /></template>
