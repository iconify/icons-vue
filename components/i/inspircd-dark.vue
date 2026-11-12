<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_zka7b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_zka7b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inspircd-dark" /></template>
