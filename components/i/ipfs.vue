<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgo9_nczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgo9_nczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ipfs" /></template>
