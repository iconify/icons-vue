<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o66p27q8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o66p27q8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-return-small" /></template>
