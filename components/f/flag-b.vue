<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc7q_ob4j.css';
import '../../css/o/oig-r-nkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="oc7q_ob4j"/><path class="oig-r-nkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flag-b" /></template>
