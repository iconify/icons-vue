<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_zac47mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_zac47mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedbase-light" /></template>
