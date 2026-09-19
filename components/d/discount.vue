<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzwz2vbkt.css';
import '../../css/r/rf258g3jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tzwz2vbkt"/><path class="rf258g3jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:discount" /></template>
