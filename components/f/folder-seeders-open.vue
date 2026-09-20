<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfig_ccgd.css';
import '../../css/g/gywkiybpr.css';
import '../../css/n/ncqivtbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":3200,"height":3200};
const content = `<path class="gfig_ccgd"/><path class="gywkiybpr"/><path class="ncqivtbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-seeders-open" /></template>
