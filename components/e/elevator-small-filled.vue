<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgmt5_ajv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dgmt5_ajv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:elevator-small-filled" /></template>
