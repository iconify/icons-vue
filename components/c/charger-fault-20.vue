<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu0zqnbaj.css';
import '../../css/n/nk5nmmbrn.css';
import '../../css/q/qm9ru_b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fu0zqnbaj"/><path class="nk5nmmbrn"/><path class="qm9ru_b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fault-20" /></template>
