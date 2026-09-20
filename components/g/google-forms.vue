<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-iyv7qyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-iyv7qyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-forms" /></template>
