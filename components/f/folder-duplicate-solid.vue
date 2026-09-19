<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/j5q8j5bgh.css';
import '../../css/e/ey9bf2odg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="j5q8j5bgh"/><path class="ey9bf2odg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-duplicate-solid" /></template>
