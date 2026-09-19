<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guvcc35_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guvcc35_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:font" /></template>
