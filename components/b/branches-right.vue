<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8t-l3beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q8t-l3beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:branches-right" /></template>
