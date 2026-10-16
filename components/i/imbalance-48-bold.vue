<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o26-z7b6y.css';
import '../../css/c/c4z6olb-l.css';
import '../../css/s/see0y-btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o26-z7b6y"/><path class="c4z6olb-l"/><path class="see0y-btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:imbalance-48-bold" /></template>
