<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scy0dybkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scy0dybkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arcade-machine-solid" /></template>
