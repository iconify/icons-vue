<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/civh5k3ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="civh5k3ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hedera" /></template>
