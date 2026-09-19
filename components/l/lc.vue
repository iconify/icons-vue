<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/krlql_bjj.css';
import '../../css/g/g20mbbbvd.css';
import '../../css/j/j8rvdj99s.css';
import '../../css/r/rqcwvnpsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="krlql_bjj"/><path class="g20mbbbvd"/><path class="j8rvdj99s"/><path class="rqcwvnpsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:lc" /></template>
