<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihh0_dbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihh0_dbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ejabberd-dark" /></template>
