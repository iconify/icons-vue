<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a08mf6bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a08mf6bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-six-small-filled" /></template>
