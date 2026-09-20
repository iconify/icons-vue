<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1-m7_38a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1-m7_38a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cplusplusbuilder" /></template>
