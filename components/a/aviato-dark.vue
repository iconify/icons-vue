<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhbb05v8s.css';
import '../../css/n/n-mc4deaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhbb05v8s"/><path class="n-mc4deaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aviato-dark" /></template>
