<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epa1joxjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epa1joxjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jfa-go-light" /></template>
