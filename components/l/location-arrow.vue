<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe5h34l0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qe5h34l0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:location-arrow" /></template>
