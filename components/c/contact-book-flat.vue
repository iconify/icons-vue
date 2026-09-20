<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s4-f90s9w.css';
import '../../css/q/qah4m-bar.css';
import '../../css/v/vcjuu9ttu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s4-f90s9w"/><path class="qah4m-bar"/><path class="vcjuu9ttu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:contact-book-flat" /></template>
