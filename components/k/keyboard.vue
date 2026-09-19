<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpax6j6zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rpax6j6zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:keyboard" /></template>
