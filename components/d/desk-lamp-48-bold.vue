<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_chr5qqn.css';
import '../../css/b/bxqwznb6j.css';
import '../../css/q/q5_trsb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u_chr5qqn"/><path class="bxqwznb6j"/><path class="q5_trsb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desk-lamp-48-bold" /></template>
