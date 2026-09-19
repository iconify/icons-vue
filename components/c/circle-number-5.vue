<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gerp8mb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gerp8mb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-5" /></template>
