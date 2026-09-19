<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-74yk_y.css';
import '../../css/u/uf53hcsyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x1-74yk_y"/><path class="uf53hcsyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exit-fill-12" /></template>
