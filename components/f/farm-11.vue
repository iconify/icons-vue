<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ammq8ggrp.css';
import '../../css/n/nss1utbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ammq8ggrp"/><path class="nss1utbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:farm-11" /></template>
