<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okdhzpq9i.css';
import '../../css/s/skok2lbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okdhzpq9i"/><path class="skok2lbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beestation" /></template>
