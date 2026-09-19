<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myb6k18tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="myb6k18tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-round-x1" /></template>
