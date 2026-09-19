<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-j9tdb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s-j9tdb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:label-small" /></template>
