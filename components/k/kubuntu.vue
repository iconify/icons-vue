<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmoxwub1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hmoxwub1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubuntu" /></template>
