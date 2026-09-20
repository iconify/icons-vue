<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_vz_ub6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v_vz_ub6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bicycle-bike-remix" /></template>
