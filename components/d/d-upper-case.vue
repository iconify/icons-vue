<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn_d-xbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":621,"height":735};
const content = `<path class="pn_d-xbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:d-upper-case" /></template>
