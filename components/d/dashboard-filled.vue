<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfry528fm.css';
import '../../css/i/iudisjbgy.css';
import '../../css/h/h0r4iwbjo.css';
import '../../css/p/p1e45sl2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="cfry528fm"/><rect class="iudisjbgy"/><rect class="h0r4iwbjo"/><rect class="p1e45sl2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dashboard-filled" /></template>
