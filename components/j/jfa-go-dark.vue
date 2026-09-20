<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwaljl50e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwaljl50e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jfa-go-dark" /></template>
