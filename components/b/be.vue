<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o575svbvu.css';
import '../../css/k/kl37bqb8y.css';
import '../../css/u/ur85n9t3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o575svbvu"/><path class="kl37bqb8y"/><path class="ur85n9t3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:be" /></template>
