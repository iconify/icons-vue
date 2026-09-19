<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngp3jeu8h.css';
import '../../css/i/ixkzetvqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngp3jeu8h"/><path class="ixkzetvqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-download" /></template>
