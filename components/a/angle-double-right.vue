<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkb969b8t.css';
import '../../css/t/trm8ypqeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lkb969b8t"/><path class="trm8ypqeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-double-right" /></template>
