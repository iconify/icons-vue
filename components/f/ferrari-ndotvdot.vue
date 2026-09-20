<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smvh7b4ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smvh7b4ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ferrari-ndotvdot" /></template>
