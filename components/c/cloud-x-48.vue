<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m77m-bb1r.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/u/uxs2crpvz.css';
import '../../css/f/fr6n2hqmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m77m-bb1r"/><path class="f5bqv3-2b"/><path class="uxs2crpvz"/><path class="fr6n2hqmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-x-48" /></template>
