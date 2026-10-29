<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0d-cmbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0d-cmbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-solid" /></template>
