<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfwxb5b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gfwxb5b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:camera" /></template>
