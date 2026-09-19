<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuofqbcfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuofqbcfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:compliance" /></template>
