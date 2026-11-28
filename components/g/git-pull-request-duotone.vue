<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9on4tfbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y9on4tfbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-pull-request-duotone" /></template>
