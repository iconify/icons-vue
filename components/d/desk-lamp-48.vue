<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sabjbxbkn.css';
import '../../css/k/kosmuobvp.css';
import '../../css/i/iln-rgb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sabjbxbkn"/><path class="kosmuobvp"/><path class="iln-rgb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desk-lamp-48" /></template>
