<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzhwxisqb.css';
import '../../css/v/vjtu4jrxy.css';
import '../../css/y/yx458593i.css';
import '../../css/h/h9vdjeyrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pzhwxisqb"/><path class="vjtu4jrxy"/><path class="yx458593i"/><path class="h9vdjeyrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-storage-48-bold" /></template>
