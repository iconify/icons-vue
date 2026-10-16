<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzhwxisqb.css';
import '../../css/q/qba5qohka.css';
import '../../css/e/ea311acjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pzhwxisqb"/><path class="qba5qohka"/><path class="ea311acjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:light-switch-48-bold" /></template>
