<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfsw2acuj.css';
import '../../css/o/oiv_48byp.css';
import '../../css/p/pvywatupn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lfsw2acuj"/><path class="oiv_48byp"/><path class="pvywatupn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kite-20" /></template>
