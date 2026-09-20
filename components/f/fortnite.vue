<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0t-dn8wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0t-dn8wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fortnite" /></template>
