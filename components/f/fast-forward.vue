<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/ec0oc1b-f.css';
import '../../css/v/v7oc-z36f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ec0oc1b-f"/><path class="v7oc-z36f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:fast-forward" /></template>
