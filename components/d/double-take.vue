<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qka7nqbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qka7nqbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:double-take" /></template>
