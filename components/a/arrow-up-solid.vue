<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohewd5--p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohewd5--p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-up-solid" /></template>
