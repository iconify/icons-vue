<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht8b8sbjq.css';
import '../../css/f/fr1_bz0hn.css';
import '../../css/o/ocqv0hbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ht8b8sbjq"/><path class="fr1_bz0hn"/><path class="ocqv0hbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-print" /></template>
