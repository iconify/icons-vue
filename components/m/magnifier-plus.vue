<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42670bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k42670bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:magnifier-plus" /></template>
