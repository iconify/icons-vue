<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma7pcqbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ma7pcqbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:inbox-solid" /></template>
