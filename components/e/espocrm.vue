<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihcuxaciq.css';
import '../../css/h/ho7n6nb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihcuxaciq"/><path class="ho7n6nb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:espocrm" /></template>
