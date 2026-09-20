<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ws7tr1v.css';
import '../../css/r/rg2p71b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-ws7tr1v"/><path class="rg2p71b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedora" /></template>
