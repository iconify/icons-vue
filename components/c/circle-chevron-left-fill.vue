<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8s03dbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p8s03dbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevron-left-fill" /></template>
