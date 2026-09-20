<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9n1396-x.css';
import '../../css/g/g-e3hmm2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9n1396-x"/><path class="g-e3hmm2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-insights" /></template>
