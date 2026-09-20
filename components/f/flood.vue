<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01qysb_c.css';
import '../../css/c/c2wp6ritf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="w01qysb_c"/><path class="c2wp6ritf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flood" /></template>
