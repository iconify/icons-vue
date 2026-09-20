<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e61q-jbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e61q-jbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:arrow-right" /></template>
