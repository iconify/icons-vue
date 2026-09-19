<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsmb_fmnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1024};
const content = `<path class="hsmb_fmnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:asterisk" /></template>
