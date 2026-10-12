<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce19mdb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ce19mdb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:header-2-20" /></template>
