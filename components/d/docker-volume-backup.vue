<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m950ohb-k.css';
import '../../css/z/z1vhpmnls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m950ohb-k"/><circle class="z1vhpmnls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docker-volume-backup" /></template>
