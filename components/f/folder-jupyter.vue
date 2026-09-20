<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbnjf8b6m.css';
import '../../css/d/dvf_gvr6i.css';
import '../../css/j/jhv07ebcm.css';
import '../../css/w/w9umcjl6q.css';
import '../../css/a/a-u3jqbpi.css';
import '../../css/s/sjgwxabga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fbnjf8b6m"/><g transform="matrix(.7 0 0 .7 5 5)" class="dvf_gvr6i"><path class="jhv07ebcm"/><circle class="w9umcjl6q"/><circle class="a-u3jqbpi"/><circle class="sjgwxabga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-jupyter" /></template>
