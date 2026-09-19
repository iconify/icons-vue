<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngcsrbb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ngcsrbb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:filters-solid" /></template>
