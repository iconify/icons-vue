<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa9ce_1pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xa9ce_1pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lldap-dark" /></template>
