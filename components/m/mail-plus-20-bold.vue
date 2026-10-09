<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z49l83-sf.css';
import '../../css/o/o9np2sbrl.css';
import '../../css/h/h5hj_ccot.css';
import '../../css/l/lfaj1l5um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z49l83-sf"/><path class="o9np2sbrl"/><path class="h5hj_ccot"/><path class="lfaj1l5um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-plus-20-bold" /></template>
