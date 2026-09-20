<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl07m8r-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl07m8r-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jamstack" /></template>
