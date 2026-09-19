<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf30-rbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf30-rbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:banknotes" /></template>
