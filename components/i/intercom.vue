<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9djxdb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z9djxdb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:intercom" /></template>
