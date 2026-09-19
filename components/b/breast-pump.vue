<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f90ii8o0l.css';
import '../../css/b/blcntivod.css';
import '../../css/i/if-72qbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f90ii8o0l"/><circle class="blcntivod"/><path class="if-72qbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:breast-pump" /></template>
