<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxg_zqbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxg_zqbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bowl-chopsticks-filled" /></template>
