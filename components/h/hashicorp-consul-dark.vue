<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/injr7pqjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="injr7pqjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-consul-dark" /></template>
