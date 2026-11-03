<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq1-gqaos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq1-gqaos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:edit-pencil-02" /></template>
