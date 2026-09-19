<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he8o9-b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="he8o9-b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-down-from-line" /></template>
