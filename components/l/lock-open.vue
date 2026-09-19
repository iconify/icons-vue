<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smr1-ljyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="smr1-ljyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:lock-open" /></template>
