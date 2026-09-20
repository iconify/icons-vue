<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cek597b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cek597b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-street-view" /></template>
