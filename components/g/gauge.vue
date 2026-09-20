<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-qc0_vlp.css';
import '../../css/a/amj39fbui.css';
import '../../css/x/xvig2ib6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="v-qc0_vlp"/><path class="amj39fbui"/><path class="xvig2ib6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:gauge" /></template>
