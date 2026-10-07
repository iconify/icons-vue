<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn69_sn7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn69_sn7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:block-default" /></template>
