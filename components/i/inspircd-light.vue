<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5kyqgb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5kyqgb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inspircd-light" /></template>
