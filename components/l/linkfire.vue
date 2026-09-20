<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd9z98brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd9z98brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:linkfire" /></template>
