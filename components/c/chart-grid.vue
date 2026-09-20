<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3rztpdiw.css';
import '../../css/l/l86idpbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3rztpdiw"/><path class="l86idpbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chart-grid" /></template>
