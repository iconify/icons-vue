<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v78_twb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v78_twb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amnezia-light" /></template>
