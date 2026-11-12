<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcbi2lbyp.css';
import '../../css/p/pckj90bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kcbi2lbyp"/><path class="pckj90bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flatnotes" /></template>
