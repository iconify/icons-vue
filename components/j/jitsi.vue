<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp77pkbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp77pkbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jitsi" /></template>
