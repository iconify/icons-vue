<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc22oabts.css';
import '../../css/b/b2k7vhb6z.css';
import '../../css/b/b_g6eybgy.css';
import '../../css/k/k565abc4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pc22oabts"/><path class="b2k7vhb6z"/><path class="b_g6eybgy"/><circle class="k565abc4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docsight-dark" /></template>
