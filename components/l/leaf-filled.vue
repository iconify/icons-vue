<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djrtgp1tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djrtgp1tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:leaf-filled" /></template>
