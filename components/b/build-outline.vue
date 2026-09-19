<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbsfahbqu.css';
import '../../css/c/cdb_1wbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbsfahbqu"/><circle class="cdb_1wbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:build-outline" /></template>
