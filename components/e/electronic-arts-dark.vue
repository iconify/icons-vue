<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwgz_dbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwgz_dbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:electronic-arts-dark" /></template>
