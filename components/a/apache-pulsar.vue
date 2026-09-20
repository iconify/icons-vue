<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcqwyrl5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcqwyrl5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-pulsar" /></template>
