<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvep-8bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvep-8bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:book-open-outline" /></template>
